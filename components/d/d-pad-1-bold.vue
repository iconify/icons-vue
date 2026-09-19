<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fparxj4eo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="fparxj4eo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:d-pad-1-bold" /></template>
