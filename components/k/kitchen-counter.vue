<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz7yl5bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gz7yl5bxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:kitchen-counter" /></template>
