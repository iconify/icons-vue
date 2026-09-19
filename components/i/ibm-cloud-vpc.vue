<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz4qtlb3x.css';
import '../../css/g/glzb1mbfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xz4qtlb3x"/><path class="glzb1mbfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-vpc" /></template>
