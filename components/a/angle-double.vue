<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gszn0u93e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="gszn0u93e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:angle-double" /></template>
