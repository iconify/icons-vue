<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk09bee9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jk09bee9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:heart-half-outline" /></template>
