<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie_odgy3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ie_odgy3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:i" /></template>
