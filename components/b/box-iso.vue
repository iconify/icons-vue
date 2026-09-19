<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2u665ban.css';
import '../../css/v/vl0ghjbbr.css';
import '../../css/a/a92sbk2qf.css';
import '../../css/r/r3wm3tj4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="k2u665ban"><path class="vl0ghjbbr"/><path class="a92sbk2qf"/><path class="r3wm3tj4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:box-iso" /></template>
