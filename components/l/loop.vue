<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdtvnc2lo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hdtvnc2lo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:loop" /></template>
