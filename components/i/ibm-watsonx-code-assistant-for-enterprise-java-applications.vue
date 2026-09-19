<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6i9drdtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t6i9drdtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-watsonx-code-assistant-for-enterprise-java-applications" /></template>
