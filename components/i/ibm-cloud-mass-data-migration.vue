<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye20y-oru.css';
import '../../css/m/mnqs348qp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ye20y-oru"/><path class="mnqs348qp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-mass-data-migration" /></template>
