<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th5jkqp1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="th5jkqp1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:in-columns" /></template>
