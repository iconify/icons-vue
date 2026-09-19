<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnimbrn0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="pnimbrn0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:angle-bold" /></template>
