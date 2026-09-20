<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0yb-g_ug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0yb-g_ug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:dropdown-list" /></template>
