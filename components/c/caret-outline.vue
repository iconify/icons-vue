<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgmbfvb2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="fgmbfvb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:caret-outline" /></template>
