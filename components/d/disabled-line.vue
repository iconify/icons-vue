<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwbocdjcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwbocdjcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:disabled-line" /></template>
