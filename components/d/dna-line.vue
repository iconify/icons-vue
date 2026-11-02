<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyv7r-wuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyv7r-wuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dna-line" /></template>
