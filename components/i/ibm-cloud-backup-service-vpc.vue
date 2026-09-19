<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j427dzbfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j427dzbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-backup-service-vpc" /></template>
