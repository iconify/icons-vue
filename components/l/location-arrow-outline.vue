<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnqen6m1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="tnqen6m1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:location-arrow-outline" /></template>
