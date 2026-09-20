<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9q4fnbbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="a9q4fnbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:candle" /></template>
