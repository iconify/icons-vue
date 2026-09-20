<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaz7o-bge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uaz7o-bge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-arrow-right-outline" /></template>
