<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u93qbxevb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u93qbxevb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:background-base-line" /></template>
