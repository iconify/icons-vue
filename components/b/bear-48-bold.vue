<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-w8eybpe.css';
import '../../css/o/oi7kg_bvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e-w8eybpe"/><path class="oi7kg_bvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bear-48-bold" /></template>
