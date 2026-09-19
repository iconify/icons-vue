<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7xn8x6wm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="a7xn8x6wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:heading-bold" /></template>
