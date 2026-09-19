<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntkv2lbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ntkv2lbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-watson-studio" /></template>
