<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m17m7eb-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m17m7eb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:building-6-fill" /></template>
