<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvef6x8av.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvef6x8av"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:laptop-2-fill" /></template>
