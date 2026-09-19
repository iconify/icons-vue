<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th7ll35oe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="th7ll35oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:dew-point-filled" /></template>
