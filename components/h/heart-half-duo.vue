<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ompinta_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ompinta_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:heart-half-duo" /></template>
