<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkmf4y6fo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="tkmf4y6fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:landmark-1" /></template>
