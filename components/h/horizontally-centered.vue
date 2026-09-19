<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3lph30dl.css';
import '../../css/x/xpua17bdp.css';
import '../../css/y/y3tc9-bzh.css';
import '../../css/t/tv_gun5-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><rect class="xpua17bdp"/><path class="y3tc9-bzh"/><path class="tv_gun5-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:horizontally-centered" /></template>
