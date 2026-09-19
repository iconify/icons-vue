<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjmakpbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="pjmakpbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:h-1" /></template>
