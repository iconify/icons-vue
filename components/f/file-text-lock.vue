<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg5se_bti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kg5se_bti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-text-lock" /></template>
