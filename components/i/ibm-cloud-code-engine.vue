<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfyj5vbtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sfyj5vbtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-code-engine" /></template>
