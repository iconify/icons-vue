<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvi-a0bav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kvi-a0bav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-secure-infrastructure-on-vpc-for-regulated-industries" /></template>
