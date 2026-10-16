<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkipg-bnu.css';
import '../../css/e/etvxrubdo.css';
import '../../css/j/j_numcn-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tkipg-bnu"/><path class="etvxrubdo"/><path class="j_numcn-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:enhanced-weathering-48" /></template>
