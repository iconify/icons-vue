<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1voi0bfp.css';
import '../../css/x/xudwaqqfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w1voi0bfp"/><path class="xudwaqqfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:hd" /></template>
