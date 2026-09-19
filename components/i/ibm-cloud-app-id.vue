<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/koq8s9beh.css';
import '../../css/k/kpiwvfbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="koq8s9beh"/><path class="kpiwvfbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-app-id" /></template>
