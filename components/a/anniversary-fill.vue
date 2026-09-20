<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orce8znyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orce8znyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:anniversary-fill" /></template>
