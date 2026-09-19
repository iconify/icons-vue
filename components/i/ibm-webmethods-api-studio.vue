<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt460bckv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nt460bckv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-webmethods-api-studio" /></template>
