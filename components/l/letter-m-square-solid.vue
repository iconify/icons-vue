<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef_187bnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ef_187bnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-m-square-solid" /></template>
