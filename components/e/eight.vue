<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqqlw_b6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="rqqlw_b6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:eight" /></template>
