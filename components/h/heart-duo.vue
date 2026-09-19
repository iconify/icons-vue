<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id3vlyjng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="id3vlyjng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:heart-duo" /></template>
