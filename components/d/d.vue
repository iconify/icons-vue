<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tna52mbvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="tna52mbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:d" /></template>
