<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6f09iaje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6f09iaje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bottle" /></template>
