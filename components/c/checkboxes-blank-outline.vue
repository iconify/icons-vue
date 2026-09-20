<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e710hqb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e710hqb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:checkboxes-blank-outline" /></template>
