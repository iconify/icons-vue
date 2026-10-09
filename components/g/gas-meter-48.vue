<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub1w7d4uf.css';
import '../../css/l/llee-cc9u.css';
import '../../css/x/xkf41wbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ub1w7d4uf"/><path class="llee-cc9u"/><path class="xkf41wbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gas-meter-48" /></template>
