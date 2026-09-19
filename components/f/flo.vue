<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe-b2tb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oe-b2tb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:flo" /></template>
