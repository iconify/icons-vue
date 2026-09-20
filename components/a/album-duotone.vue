<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/ghye6ac_s.css';
import '../../css/q/q-qszr_we.css';
import '../../css/x/xzbd7ubcv.css';
import '../../css/c/c9aqz6byz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ghye6ac_s"/><path clip-rule="evenodd" class="q-qszr_we"/><path class="xzbd7ubcv"/><path class="c9aqz6byz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:album-duotone" /></template>
