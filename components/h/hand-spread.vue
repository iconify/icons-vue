<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9uv-zbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="b9uv-zbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-spread" /></template>
