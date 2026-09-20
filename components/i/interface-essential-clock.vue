<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kybmc_b1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kybmc_b1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-clock" /></template>
