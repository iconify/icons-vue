<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_ijcklcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r_ijcklcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:bpmn-error-fill" /></template>
