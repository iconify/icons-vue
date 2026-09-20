<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/meyp7-bkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="meyp7-bkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:9" /></template>
