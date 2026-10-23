<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozg9a2b_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ozg9a2b_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-sterling-b2b-integration-saas" /></template>
