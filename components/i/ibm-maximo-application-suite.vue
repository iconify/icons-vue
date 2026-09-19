<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipb3veb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ipb3veb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-maximo-application-suite" /></template>
