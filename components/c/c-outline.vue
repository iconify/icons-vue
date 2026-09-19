<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arknlwboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="arknlwboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:c-outline" /></template>
