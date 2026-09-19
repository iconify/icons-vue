<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbiso1wff.css';
import '../../css/y/yhignzrec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mbiso1wff"/><path class="yhignzrec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-evaluation" /></template>
