<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owsm1-kve.css';
import '../../css/b/b1rupy8li.css';
import '../../css/y/ybmkcumuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="owsm1-kve"/><path class="b1rupy8li"/><path class="ybmkcumuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:business-products-performance-money-increase" /></template>
