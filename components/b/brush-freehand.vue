<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsbj687dq.css';
import '../../css/a/aib90vbtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tsbj687dq"/><path class="aib90vbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:brush-freehand" /></template>
