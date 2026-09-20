<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4i0jpbcr.css';
import '../../css/w/w5v8e733c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l4i0jpbcr"/><path class="w5v8e733c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-stat" /></template>
