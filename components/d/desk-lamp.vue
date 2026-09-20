<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csd7vtbst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="csd7vtbst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:desk-lamp" /></template>
