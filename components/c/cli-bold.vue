<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elmbf2wzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="elmbf2wzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:cli-bold" /></template>
