<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad2pn_1bn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ad2pn_1bn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-software-watsonx-data-structured-import" /></template>
