<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lywu_-b-a.css';
import '../../css/u/uzq_ldbqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lywu_-b-a"/><path class="uzq_ldbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:box-large" /></template>
