<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t68lgib2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="t68lgib2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:diamond-bold" /></template>
