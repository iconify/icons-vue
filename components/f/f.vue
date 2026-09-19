<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f13jpybpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="f13jpybpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:f" /></template>
