<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yazykqgsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="yazykqgsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:b-bold" /></template>
