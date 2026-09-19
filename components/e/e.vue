<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip9anpq2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ip9anpq2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:e" /></template>
