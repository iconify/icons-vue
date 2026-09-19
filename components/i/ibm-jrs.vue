<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmu8ssxvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hmu8ssxvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-jrs" /></template>
