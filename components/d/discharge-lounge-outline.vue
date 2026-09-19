<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wfb-nmuvg.css';
import '../../css/z/zwu2hyb8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="wfb-nmuvg"/><path clip-rule="evenodd" class="zwu2hyb8k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:discharge-lounge-outline" /></template>
