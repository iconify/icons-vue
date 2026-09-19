<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_m8u_bjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="c_m8u_bjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:die-3-bold" /></template>
