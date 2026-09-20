<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mita_xbuw.css';
import '../../css/r/r8_oqnbcm.css';
import '../../css/s/su1i-1q6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mita_xbuw"/><path class="r8_oqnbcm"/><path clip-rule="evenodd" class="su1i-1q6z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:donut-filled" /></template>
