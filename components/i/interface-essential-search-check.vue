<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj0d_qbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qj0d_qbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-search-check" /></template>
