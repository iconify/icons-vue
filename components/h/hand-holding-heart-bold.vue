<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrn3rpbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="rrn3rpbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-holding-heart-bold" /></template>
