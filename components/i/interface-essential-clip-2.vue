<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8-rf8aoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r8-rf8aoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-clip-2" /></template>
