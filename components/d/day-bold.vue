<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otortxb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="otortxb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:day-bold" /></template>
