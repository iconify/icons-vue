<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjpyy0hsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="vjpyy0hsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:adjust" /></template>
