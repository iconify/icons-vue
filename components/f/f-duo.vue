<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1k6oyamb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="l1k6oyamb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:f-duo" /></template>
