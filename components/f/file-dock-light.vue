<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/i/irzp74b2d.css';
import '../../css/l/lepgkoxkn.css';
import '../../css/f/fvhj0vbhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="irzp74b2d"/><path class="lepgkoxkn"/><path class="fvhj0vbhb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:file-dock-light" /></template>
