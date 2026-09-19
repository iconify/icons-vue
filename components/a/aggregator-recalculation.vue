<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhq8vgbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hhq8vgbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:aggregator-recalculation" /></template>
