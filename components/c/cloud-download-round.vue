<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjfga9bzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjfga9bzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-download-round" /></template>
