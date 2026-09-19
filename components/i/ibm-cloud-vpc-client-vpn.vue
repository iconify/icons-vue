<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x77484beb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x77484beb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-vpc-client-vpn" /></template>
