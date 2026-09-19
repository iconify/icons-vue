<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytj3mk6kx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ytj3mk6kx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:grid-sm-bold" /></template>
