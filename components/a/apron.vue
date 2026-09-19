<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oay1xn8pl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="oay1xn8pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:apron" /></template>
