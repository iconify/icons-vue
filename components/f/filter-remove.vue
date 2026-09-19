<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqjus3b5f.css';
import '../../css/c/ch2vo1b_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uqjus3b5f"/><path class="ch2vo1b_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:filter-remove" /></template>
