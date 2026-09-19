<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7r46xbio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="g7r46xbio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:export-mirrored" /></template>
