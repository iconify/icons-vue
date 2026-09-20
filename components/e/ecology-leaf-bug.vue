<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0tgts-yf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e0tgts-yf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:ecology-leaf-bug" /></template>
