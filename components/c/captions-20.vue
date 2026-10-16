<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4l8cxbpg.css';
import '../../css/h/hxs084q0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t4l8cxbpg"/><path class="hxs084q0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:captions-20" /></template>
