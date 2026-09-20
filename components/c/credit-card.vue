<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pxstb9b1h.css';
import '../../css/w/wh2k3y_4b.css';
import '../../css/c/cn6m43jim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="pxstb9b1h"/><path clip-rule="evenodd" class="wh2k3y_4b"/><path clip-rule="evenodd" class="cn6m43jim"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:credit-card" /></template>
