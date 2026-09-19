<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhtfhzbpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="mhtfhzbpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:heart-1-outline" /></template>
