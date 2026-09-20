<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka_x1487y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ka_x1487y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:house-modern" /></template>
