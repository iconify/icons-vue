<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzef6e9ev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="gzef6e9ev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:code" /></template>
