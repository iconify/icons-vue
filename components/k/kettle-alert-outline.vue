<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss84kbcny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ss84kbcny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:kettle-alert-outline" /></template>
