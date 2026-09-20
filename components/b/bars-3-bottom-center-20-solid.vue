<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/varzj22qh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="varzj22qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:bars-3-bottom-center-20-solid" /></template>
