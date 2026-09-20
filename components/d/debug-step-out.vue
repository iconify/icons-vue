<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcbzydbdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcbzydbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:debug-step-out" /></template>
