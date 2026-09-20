<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl2074zep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dl2074zep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:contract-right-line" /></template>
