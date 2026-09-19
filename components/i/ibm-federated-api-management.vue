<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igwhek31a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="igwhek31a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-federated-api-management" /></template>
