<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9-4w-bok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":72};
const content = `<path class="o9-4w-bok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:firecrawl-dark" /></template>
