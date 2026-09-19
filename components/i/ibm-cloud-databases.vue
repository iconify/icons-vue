<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rytaa1bmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rytaa1bmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-databases" /></template>
