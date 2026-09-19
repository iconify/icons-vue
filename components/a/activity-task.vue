<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucqddvbtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ucqddvbtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:activity-task" /></template>
