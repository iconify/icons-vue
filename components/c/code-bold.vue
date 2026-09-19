<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnc7j12jl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="cnc7j12jl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:code-bold" /></template>
