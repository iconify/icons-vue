<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke6bw-_7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="ke6bw-_7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-thin-left-top" /></template>
