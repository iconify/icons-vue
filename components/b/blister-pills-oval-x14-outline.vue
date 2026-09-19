<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fh13o9bct.css';
import '../../css/e/eqj9trbhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="fh13o9bct"/><path clip-rule="evenodd" class="eqj9trbhr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blister-pills-oval-x14-outline" /></template>
