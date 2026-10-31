<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m538sebkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m538sebkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-filter-fill-round" /></template>
