<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0nc_fbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0nc_fbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:coinbase" /></template>
