<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rf1lcdbbf.css';
import '../../css/l/li-08qb4y.css';
import '../../css/n/nrth2abtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rf1lcdbbf"/><path class="li-08qb4y"/><path class="nrth2abtj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:chromecast" /></template>
