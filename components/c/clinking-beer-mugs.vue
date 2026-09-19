<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sg2f8hkpu.css';
import '../../css/j/juigwbcmn.css';
import '../../css/v/v2o85f3kl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="sg2f8hkpu"/><path class="juigwbcmn"/><path class="v2o85f3kl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:clinking-beer-mugs" /></template>
