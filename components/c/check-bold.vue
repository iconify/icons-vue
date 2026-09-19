<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj4vyycmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="fj4vyycmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:check-bold" /></template>
