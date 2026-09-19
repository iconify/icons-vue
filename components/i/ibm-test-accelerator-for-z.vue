<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2mgj9h3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k2mgj9h3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-test-accelerator-for-z" /></template>
