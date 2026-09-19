<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2-m7dbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="i2-m7dbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bed" /></template>
