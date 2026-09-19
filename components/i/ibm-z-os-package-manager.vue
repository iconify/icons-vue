<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx2yo906k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kx2yo906k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-z-os-package-manager" /></template>
