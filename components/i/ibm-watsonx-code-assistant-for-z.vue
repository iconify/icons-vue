<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzk7dyusq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gzk7dyusq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-watsonx-code-assistant-for-z" /></template>
