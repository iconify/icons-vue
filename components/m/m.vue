<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pax50ybav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="pax50ybav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:m" /></template>
