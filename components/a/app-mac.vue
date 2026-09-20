<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw06-bcsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw06-bcsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:app-mac" /></template>
