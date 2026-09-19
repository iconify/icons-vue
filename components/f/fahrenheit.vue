<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v30e2vbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="v30e2vbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:fahrenheit" /></template>
