<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/y/yz6cc9brd.css';
import '../../css/s/sra97_a6j.css';
import '../../css/l/lo0kr2blb.css';
import '../../css/m/m7lonbwkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco yz6cc9brd"/><path class="sra97_a6j wm-deco"/><path class="lo0kr2blb wm-k"/><path class="m7lonbwkx wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:list-filter-blueprint" /></template>
