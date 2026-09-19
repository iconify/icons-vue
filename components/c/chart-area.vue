<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_fbkkbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n_fbkkbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-area" /></template>
