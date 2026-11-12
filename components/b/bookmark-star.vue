<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee9p8obgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee9p8obgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bookmark-star" /></template>
