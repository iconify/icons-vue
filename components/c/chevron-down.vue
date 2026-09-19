<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_8-1rbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_8-1rbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chevron-down" /></template>
