<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1zr6vb5v.css';
import '../../css/e/ee-m9bcyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u1zr6vb5v"/><path class="ee-m9bcyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:clean" /></template>
