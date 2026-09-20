<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/liim8eenz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="liim8eenz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-hierarchy-4" /></template>
