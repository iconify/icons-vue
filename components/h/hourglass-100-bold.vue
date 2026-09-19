<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-lsfljsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="d-lsfljsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hourglass-100-bold" /></template>
