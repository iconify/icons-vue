<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5t413bgn.css';
import '../../css/o/oktelfbts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w5t413bgn"/><path class="oktelfbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-view-eye" /></template>
