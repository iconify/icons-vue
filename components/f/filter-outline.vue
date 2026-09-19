<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbkvdeb4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="nbkvdeb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:filter-outline" /></template>
