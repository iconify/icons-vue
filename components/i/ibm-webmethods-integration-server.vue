<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbopcgp3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lbopcgp3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-webmethods-integration-server" /></template>
