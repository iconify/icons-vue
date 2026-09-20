<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbz6_zhjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbz6_zhjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-up-z-a" /></template>
