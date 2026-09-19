<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx0iropur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="rx0iropur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:exclamation-duo" /></template>
