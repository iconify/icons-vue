<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv0n9ebsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hv0n9ebsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-application-and-discovery-delivery-intelligence" /></template>
