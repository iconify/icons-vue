<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojx-05bwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojx-05bwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:accessibility-fill" /></template>
