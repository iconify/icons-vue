<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzgwfsg3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="rzgwfsg3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:cloud-duo" /></template>
