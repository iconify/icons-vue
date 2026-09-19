<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8ws7ybzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="r8ws7ybzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:grin-squint-bold" /></template>
