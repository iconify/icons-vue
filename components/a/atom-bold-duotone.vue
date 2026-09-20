<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/tiiyrjvgi.css';
import '../../css/p/pv1rl1bal.css';
import '../../css/a/adqqsio1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tiiyrjvgi"/><path class="pv1rl1bal"/><path class="adqqsio1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:atom-bold-duotone" /></template>
