<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxmi4xbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="gxmi4xbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:h-1-outline" /></template>
