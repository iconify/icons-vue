<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1_h_fbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p1_h_fbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-app-connect-enterprise" /></template>
