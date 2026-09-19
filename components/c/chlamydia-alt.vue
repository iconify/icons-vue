<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gu71owqar.css';
import '../../css/i/isras2boi.css';
import '../../css/r/r8sdp5bdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="gu71owqar"/><path clip-rule="evenodd" class="isras2boi"/><path class="r8sdp5bdc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:chlamydia-alt" /></template>
