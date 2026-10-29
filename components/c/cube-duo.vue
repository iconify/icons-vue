<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/f8kxdpb_h.css';
import '../../css/e/ev6-t-xbj.css';
import '../../css/f/f1iyce6_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="f8kxdpb_h"/><path class="ev6-t-xbj wm-a"/><path class="f1iyce6_y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cube-duo" /></template>
