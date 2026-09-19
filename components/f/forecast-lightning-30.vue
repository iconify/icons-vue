<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kznva-0mg.css';
import '../../css/g/gvmh5mbbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kznva-0mg"/><path class="gvmh5mbbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:forecast-lightning-30" /></template>
