<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dved3o4nz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dved3o4nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-arrow-up" /></template>
