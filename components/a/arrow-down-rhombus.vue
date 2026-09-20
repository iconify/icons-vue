<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr9vg-bzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sr9vg-bzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-down-rhombus" /></template>
