<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu66jk8uv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vu66jk8uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:coat-hanger" /></template>
