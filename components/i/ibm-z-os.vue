<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkc89nbke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jkc89nbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-z-os" /></template>
