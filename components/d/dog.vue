<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4o9b8mlh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w4o9b8mlh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:dog" /></template>
