<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/huwc7bvri.css';
import '../../css/o/ohu1b7g7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="huwc7bvri"/><path clip-rule="evenodd" class="ohu1b7g7p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:magnifying-glass-expressive" /></template>
