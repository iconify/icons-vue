<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy7a12bwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1728};
const content = `<path class="vy7a12bwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:line" /></template>
