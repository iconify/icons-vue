<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvxjx97jd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="dvxjx97jd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:canoe-2-outline" /></template>
