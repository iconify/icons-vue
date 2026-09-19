<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6n_bjbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s6n_bjbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-line-smooth" /></template>
