<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf_710lax.css';
import '../../css/o/o-x0dsblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yf_710lax"/><path class="o-x0dsblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:forecast-lightning" /></template>
