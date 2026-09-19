<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8hhtkv4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p8hhtkv4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-security" /></template>
