<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzgt7sboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzgt7sboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fridge-line" /></template>
