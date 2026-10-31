<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fxnrcmbcl.css';
import '../../css/l/ll4ui7hzo.css';
import '../../css/c/caxhh42oz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="fxnrcmbcl"/><path clip-rule="evenodd" class="ll4ui7hzo"/><path class="caxhh42oz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:drop-medicine" /></template>
