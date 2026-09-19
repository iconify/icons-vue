<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz4cr67ul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xz4cr67ul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-watson-text-to-speech" /></template>
