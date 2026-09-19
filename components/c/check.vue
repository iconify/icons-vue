<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1j28zb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="w1j28zb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:check" /></template>
