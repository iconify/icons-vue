<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cik2l7bjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="cik2l7bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hourglass-bold" /></template>
