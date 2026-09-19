<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi_4_2dxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vi_4_2dxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:airline-rapid-board" /></template>
