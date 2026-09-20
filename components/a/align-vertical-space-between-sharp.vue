<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e171jac_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e171jac_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-vertical-space-between-sharp" /></template>
