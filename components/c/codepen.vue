<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz941qnwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="sz941qnwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:codepen" /></template>
