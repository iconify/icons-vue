<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewp8hnbgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ewp8hnbgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:five-bold" /></template>
