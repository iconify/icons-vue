<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7s7dcjej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7s7dcjej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:exclude-fill" /></template>
