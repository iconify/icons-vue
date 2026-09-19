<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1_96iyla.css';
import '../../css/j/j7l2cq2fe.css';
import '../../css/y/yt-bzx_hx.css';
import '../../css/s/s22tbkbrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="j1_96iyla"/><path class="j7l2cq2fe"/><path class="yt-bzx_hx"/><path class="s22tbkbrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:gh-4x3" /></template>
