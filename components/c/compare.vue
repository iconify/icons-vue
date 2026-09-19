<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzpkb4b_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jzpkb4b_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:compare" /></template>
