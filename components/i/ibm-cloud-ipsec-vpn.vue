<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz405v0af.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oz405v0af"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-ipsec-vpn" /></template>
