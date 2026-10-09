<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qypcfebhs.css';
import '../../css/e/e8j_nwbgk.css';
import '../../css/b/by5qfxf8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qypcfebhs"/><path class="e8j_nwbgk"/><path class="by5qfxf8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:garage-20" /></template>
