<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2_fj7bbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":72};
const content = `<path class="d2_fj7bbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:firecrawl-light" /></template>
