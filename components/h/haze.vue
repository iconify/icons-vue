<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q99sspbda.css';
import '../../css/t/tayu-xb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q99sspbda"/><path class="tayu-xb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:haze" /></template>
