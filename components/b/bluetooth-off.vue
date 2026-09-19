<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu2ffabve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bu2ffabve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:bluetooth-off" /></template>
