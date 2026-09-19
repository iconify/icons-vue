<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh-ng8b3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dh-ng8b3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:chart-bar-stacked-outline-24px" /></template>
