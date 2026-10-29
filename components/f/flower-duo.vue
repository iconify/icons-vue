<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/slmd9ybfi.css';
import '../../css/h/hbi8hhkfx.css';
import '../../css/z/zyla41bsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="slmd9ybfi"/><path class="hbi8hhkfx wm-a"/><path class="zyla41bsz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:flower-duo" /></template>
