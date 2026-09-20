<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k43-1iple.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k43-1iple"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:code-ai" /></template>
