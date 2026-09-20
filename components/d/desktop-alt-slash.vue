<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6h29rbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6h29rbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:desktop-alt-slash" /></template>
