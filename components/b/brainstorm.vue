<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0fx791qe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l0fx791qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:brainstorm" /></template>
