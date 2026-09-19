<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi655acym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="fi655acym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:heart-half-1" /></template>
