<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eddq2pbon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eddq2pbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-bluepay" /></template>
