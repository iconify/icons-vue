<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktgsm8eun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktgsm8eun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:aas-project-tia" /></template>
