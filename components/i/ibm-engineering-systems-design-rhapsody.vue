<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unk65rxam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="unk65rxam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-engineering-systems-design-rhapsody" /></template>
