<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxix6l8rl.css';
import '../../css/h/hy4ycj-aj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cxix6l8rl"/><path class="hy4ycj-aj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:charging-station" /></template>
