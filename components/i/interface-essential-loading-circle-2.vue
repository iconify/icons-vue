<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3c-7tb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a3c-7tb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-loading-circle-2" /></template>
