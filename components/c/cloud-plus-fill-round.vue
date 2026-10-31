<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5_gb5e-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5_gb5e-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-plus-fill-round" /></template>
