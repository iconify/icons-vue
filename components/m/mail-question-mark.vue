<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va_2e8zin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="va_2e8zin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:mail-question-mark" /></template>
