<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxo10u8ki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="xxo10u8ki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:adjust-1-bold" /></template>
