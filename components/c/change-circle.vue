<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjnu8mbcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gjnu8mbcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:change-circle" /></template>
