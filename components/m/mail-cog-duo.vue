<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdc3ghf8g.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/h1ma72bft.css';
import '../../css/l/llr9rqbjq.css';
import '../../css/d/dq60wlbxs.css';
import '../../css/b/b9him6jfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary tdc3ghf8g"/><g class="dt0cm9dhy primary"><path class="h1ma72bft"/><path class="llr9rqbjq"/><path class="dq60wlbxs"/><path class="b9him6jfk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mail-cog-duo" /></template>
