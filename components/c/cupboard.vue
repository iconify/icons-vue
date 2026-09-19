<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_0c644vy.css';
import '../../css/q/q4_c29bvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_0c644vy"/><path class="q4_c29bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cupboard" /></template>
