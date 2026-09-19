<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdu2pbcie.css';
import '../../css/z/z8gtf7k7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kdu2pbcie"/><path class="z8gtf7k7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document-horizontal" /></template>
