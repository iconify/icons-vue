<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oryax0bnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="oryax0bnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:box-1-outline" /></template>
