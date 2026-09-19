<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/s/sktjwobeu.css';
import '../../css/d/dwm4owi0d.css';
import '../../css/y/yl2fcsb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="sktjwobeu"/><circle class="dwm4owi0d"/><path class="yl2fcsb_p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:disabled-computer" /></template>
