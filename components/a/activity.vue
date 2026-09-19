<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj35mhboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="aj35mhboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:activity" /></template>
