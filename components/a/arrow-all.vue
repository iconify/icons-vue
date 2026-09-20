<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8_c7cbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8_c7cbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-all" /></template>
