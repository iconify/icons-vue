<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a-oytwb8e.css';
import '../../css/b/bqnwlwbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="a-oytwb8e"/><path clip-rule="evenodd" class="bqnwlwbde"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:cervical-cancer" /></template>
