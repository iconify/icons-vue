<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/ucnsm_buf.css';
import '../../css/k/kcfhar2al.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ucnsm_buf"/><path clip-rule="evenodd" class="kcfhar2al"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:headphones-sound2-filled" /></template>
