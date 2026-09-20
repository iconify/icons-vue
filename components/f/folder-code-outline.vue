<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i6d87qbmc.css';
import '../../css/i/iig8wobze.css';
import '../../css/w/wzr4wqbzt.css';
import '../../css/w/w_8fmvbbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i6d87qbmc"/><path class="iig8wobze"/><path class="wzr4wqbzt"/><path clip-rule="evenodd" class="w_8fmvbbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-code-outline" /></template>
