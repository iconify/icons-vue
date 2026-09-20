<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q46jpx5lh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q46jpx5lh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:array-light" /></template>
