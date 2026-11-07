<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsdupsbro.css';
import '../../css/v/vu18-_bab.css';
import '../../css/l/lg9shfpyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dsdupsbro"/><path class="vu18-_bab"/><path class="lg9shfpyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:expressionless-circle-outline" /></template>
