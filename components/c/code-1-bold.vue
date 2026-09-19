<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn-yezbjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="pn-yezbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:code-1-bold" /></template>
