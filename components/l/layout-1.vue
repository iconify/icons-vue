<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqa9kzqsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="oqa9kzqsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:layout-1" /></template>
