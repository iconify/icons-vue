<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3n38s0_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3n38s0_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-left-to-line-fill-round" /></template>
