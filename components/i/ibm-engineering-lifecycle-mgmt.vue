<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc5g2nboj.css';
import '../../css/s/s4u93xkgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nc5g2nboj"/><path class="s4u93xkgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-engineering-lifecycle-mgmt" /></template>
