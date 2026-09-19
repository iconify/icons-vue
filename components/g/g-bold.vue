<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/garrj2qto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="garrj2qto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:g-bold" /></template>
