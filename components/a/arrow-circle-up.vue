<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfpj2xyvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mfpj2xyvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:arrow-circle-up" /></template>
