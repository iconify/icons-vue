<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4-1q-b0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4-1q-b0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-big-left-short-fill" /></template>
