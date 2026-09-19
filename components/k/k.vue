<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpqs12bkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="xpqs12bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:k" /></template>
