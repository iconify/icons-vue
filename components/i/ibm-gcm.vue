<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxujzib5b.css';
import '../../css/o/okc6ec79j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jxujzib5b"/><path class="okc6ec79j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-gcm" /></template>
