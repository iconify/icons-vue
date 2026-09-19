<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yom7c30uv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="yom7c30uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:chevron-circle-bold" /></template>
