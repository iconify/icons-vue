<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0op70bmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="a0op70bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:location-arrow-duo" /></template>
