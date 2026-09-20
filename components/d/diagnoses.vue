<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb4eypbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eb4eypbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:diagnoses" /></template>
