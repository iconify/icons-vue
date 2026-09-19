<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0i85cboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l0i85cboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:edt-loop" /></template>
