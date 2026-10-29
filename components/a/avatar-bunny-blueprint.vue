<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/f/fl-_d0bxx.css';
import '../../css/s/s0bn3tbfk.css';
import '../../css/j/jlfuetb9g.css';
import '../../css/y/y2dh5ifmd.css';
import '../../css/k/kevts6bge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="fl-_d0bxx wm-deco"/><path class="s0bn3tbfk wm-deco"/><path class="jlfuetb9g wm-deco"/><path class="wm-k y2dh5ifmd"/><path class="kevts6bge wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-bunny-blueprint" /></template>
