<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo7wix1lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="uo7wix1lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:book-spine" /></template>
