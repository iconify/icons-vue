<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkkhz-2jy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tkkhz-2jy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-i" /></template>
