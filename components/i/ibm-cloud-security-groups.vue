<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpn-fce2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fpn-fce2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-security-groups" /></template>
