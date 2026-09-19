<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orw8s647j.css';
import '../../css/f/fwvo6n8hv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="orw8s647j"/><path class="fwvo6n8hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:filter-edit" /></template>
