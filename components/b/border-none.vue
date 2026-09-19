<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy8lgtbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="gy8lgtbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:border-none" /></template>
