<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-ft2r-zd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":480};
const content = `<path class="i-ft2r-zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:format-valign-center" /></template>
