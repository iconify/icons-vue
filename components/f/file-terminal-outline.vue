<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/znp_bzbzb.css';
import '../../css/p/ps46_kbzm.css';
import '../../css/f/f_7mvhbyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="znp_bzbzb"/><path class="ps46_kbzm"/><path clip-rule="evenodd" class="f_7mvhbyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-terminal-outline" /></template>
