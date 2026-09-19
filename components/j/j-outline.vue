<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukp4s0b3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ukp4s0b3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:j-outline" /></template>
