<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er-2y1b7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er-2y1b7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:heading-5" /></template>
