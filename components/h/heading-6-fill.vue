<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-0dsebfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-0dsebfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heading-6-fill" /></template>
