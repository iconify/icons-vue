<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kldbyvy5v.css';
import '../../css/k/kaj75h1kd.css';
import '../../css/u/ux63s-ozf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="kldbyvy5v"/><path class="kaj75h1kd"/><path class="ux63s-ozf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:checkmark-print" /></template>
