<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j84_xvb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="j84_xvb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:globe-stand-outline" /></template>
