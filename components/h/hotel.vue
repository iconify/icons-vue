<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/meoi9rbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="meoi9rbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hotel" /></template>
