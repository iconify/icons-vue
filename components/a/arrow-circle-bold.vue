<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2if9lbnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="m2if9lbnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-circle-bold" /></template>
