<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw9u8dbku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xw9u8dbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-line" /></template>
