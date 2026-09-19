<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0xpi2b-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="s0xpi2b-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:box-1-bold" /></template>
