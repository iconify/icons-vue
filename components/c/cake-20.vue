<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydgeh8l8d.css';
import '../../css/y/yp7spr8cr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ydgeh8l8d"/><path class="yp7spr8cr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cake-20" /></template>
