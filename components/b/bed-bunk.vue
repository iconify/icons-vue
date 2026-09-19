<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-1rd3zwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="y-1rd3zwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bed-bunk" /></template>
