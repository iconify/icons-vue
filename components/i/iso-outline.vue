<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qiv05cixr.css';
import '../../css/w/w1voi0bfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qiv05cixr"/><path class="w1voi0bfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:iso-outline" /></template>
