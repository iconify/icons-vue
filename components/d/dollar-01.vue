<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo96n54an.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo96n54an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dollar-01" /></template>
