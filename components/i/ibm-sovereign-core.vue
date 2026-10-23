<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwzr2q6id.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nwzr2q6id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-sovereign-core" /></template>
