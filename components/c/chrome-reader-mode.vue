<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_pzvlfgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_pzvlfgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chrome-reader-mode" /></template>
