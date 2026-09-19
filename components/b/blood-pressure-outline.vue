<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hyiumx5dq.css';
import '../../css/s/szz0j1wwy.css';
import '../../css/x/x26wrsjtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="hyiumx5dq"/><path class="szz0j1wwy"/><path clip-rule="evenodd" class="x26wrsjtl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blood-pressure-outline" /></template>
