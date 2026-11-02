<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7gvm6bzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7gvm6bzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:exit-door-fill" /></template>
