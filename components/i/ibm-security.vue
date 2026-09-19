<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlg1h8epy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vlg1h8epy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-security" /></template>
