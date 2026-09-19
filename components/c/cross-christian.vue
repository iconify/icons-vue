<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cskp9py_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="cskp9py_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:cross-christian" /></template>
