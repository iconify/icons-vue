<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5_6rlexd.css';
import '../../css/x/xgumicc2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p5_6rlexd"/><path class="xgumicc2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-security-compliance-center" /></template>
