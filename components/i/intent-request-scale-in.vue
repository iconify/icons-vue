<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gffi6mjqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gffi6mjqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:intent-request-scale-in" /></template>
