<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq3_z1b5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fq3_z1b5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:letter-ii" /></template>
