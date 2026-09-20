<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbc_w3bzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbc_w3bzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:drag-move-line" /></template>
