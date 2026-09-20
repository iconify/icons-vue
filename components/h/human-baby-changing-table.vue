<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kywogzbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kywogzbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:human-baby-changing-table" /></template>
