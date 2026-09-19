<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2uo85bzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="k2uo85bzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bookmark" /></template>
