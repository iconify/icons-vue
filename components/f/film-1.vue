<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omfe1vp1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="omfe1vp1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:film-1" /></template>
