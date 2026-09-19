<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asfl_abgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="asfl_abgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:letter-nn" /></template>
