<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf66svvni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xf66svvni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:collapse-categories" /></template>
