<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-h1lxbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v-h1lxbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-pak-manta-automated-data-lineage" /></template>
