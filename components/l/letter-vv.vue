<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksq4q7bdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ksq4q7bdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:letter-vv" /></template>
