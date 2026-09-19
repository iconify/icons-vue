<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxy3m40ml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="kxy3m40ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:cursor-outline" /></template>
