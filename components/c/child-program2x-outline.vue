<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/isx6mgsxv.css';
import '../../css/f/fo7gwhhcs.css';
import '../../css/l/lt6a2ib8u.css';
import '../../css/g/gdl6gfbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="isx6mgsxv"/><path class="fo7gwhhcs"/><path clip-rule="evenodd" class="lt6a2ib8u"/><path class="gdl6gfbni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:child-program2x-outline" /></template>
