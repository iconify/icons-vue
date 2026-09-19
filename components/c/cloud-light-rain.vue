<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5yf1eshv.css';
import '../../css/t/toc-9jzis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5yf1eshv"/><path class="toc-9jzis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:cloud-light-rain" /></template>
