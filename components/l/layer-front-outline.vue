<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgm1yzbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="zgm1yzbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:layer-front-outline" /></template>
