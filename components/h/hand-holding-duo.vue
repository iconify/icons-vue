<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyq7mlb0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="iyq7mlb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-holding-duo" /></template>
