<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdv1--bmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdv1--bmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-end-horizontal" /></template>
