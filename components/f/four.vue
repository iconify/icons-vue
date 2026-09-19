<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll7kddc1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ll7kddc1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:four" /></template>
