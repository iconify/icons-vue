<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fidptbk8m.css';
import '../../css/v/vb_01fboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fidptbk8m"/><path class="vb_01fboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-waterfall" /></template>
