<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_n7hgyks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="i_n7hgyks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:angle" /></template>
