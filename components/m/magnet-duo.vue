<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/doivh7blh.css';
import '../../css/f/fcpcu9i2b.css';
import '../../css/j/jura4nbok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="doivh7blh"/><path class="fcpcu9i2b wm-a"/><path class="jura4nbok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:magnet-duo" /></template>
