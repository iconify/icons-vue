<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6e58ubjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="a6e58ubjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:border-none-bold" /></template>
