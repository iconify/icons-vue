<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt1_pr37r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mt1_pr37r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-up-drop-circle" /></template>
