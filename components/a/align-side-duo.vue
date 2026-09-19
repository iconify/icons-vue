<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zahkbf3tz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="zahkbf3tz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:align-side-duo" /></template>
