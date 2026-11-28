<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugwp1vfjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ugwp1vfjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dispensing-machine-with-handled-teacup-and-saucer" /></template>
