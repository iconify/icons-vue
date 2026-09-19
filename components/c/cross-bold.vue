<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyn8p9byz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="tyn8p9byz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:cross-bold" /></template>
