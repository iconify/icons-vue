<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzxetnbiv.css';
import '../../css/x/xdjatpcmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gzxetnbiv"/><path class="xdjatpcmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:intersect" /></template>
