<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5c_1dupa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="j5c_1dupa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-line-start" /></template>
