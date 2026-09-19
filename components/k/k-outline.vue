<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy7mr6luy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="vy7mr6luy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:k-outline" /></template>
