<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz38x801z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kz38x801z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-big-left" /></template>
