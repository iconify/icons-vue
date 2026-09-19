<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzyvr_bnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="rzyvr_bnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bars-offset" /></template>
