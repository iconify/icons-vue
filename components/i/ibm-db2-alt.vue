<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enisynbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="enisynbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-db2-alt" /></template>
