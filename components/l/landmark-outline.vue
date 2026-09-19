<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk5q1p-7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="tk5q1p-7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:landmark-outline" /></template>
