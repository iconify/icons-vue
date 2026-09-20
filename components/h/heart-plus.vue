<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7hz3j1pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7hz3j1pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:heart-plus" /></template>
