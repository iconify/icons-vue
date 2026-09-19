<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtknkcbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="rtknkcbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:circle-half-2-outline" /></template>
