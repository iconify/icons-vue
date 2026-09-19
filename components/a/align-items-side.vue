<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v01kf7p0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="v01kf7p0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:align-items-side" /></template>
