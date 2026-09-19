<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njm8qsxea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="njm8qsxea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:diamond-1-outline" /></template>
