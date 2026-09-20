<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mtm74unlw.css';
import '../../css/o/o91c38lko.css';
import '../../css/q/q3g2voh6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mtm74unlw"/><path class="o91c38lko"/><path clip-rule="evenodd" class="q3g2voh6e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:banknote-2-bold" /></template>
