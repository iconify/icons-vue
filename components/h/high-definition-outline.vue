<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f2gxr5bwv.css';
import '../../css/l/l8jkf64ne.css';
import '../../css/b/bbrv0_ogo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f2gxr5bwv"/><path clip-rule="evenodd" class="l8jkf64ne"/><path clip-rule="evenodd" class="bbrv0_ogo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:high-definition-outline" /></template>
