<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owsm1-kve.css';
import '../../css/j/j-exd4cnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="owsm1-kve"/><path class="j-exd4cnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:business-products-performance-money-decrease" /></template>
