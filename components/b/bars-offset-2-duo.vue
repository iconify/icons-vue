<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4d1rx7fp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="w4d1rx7fp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bars-offset-2-duo" /></template>
