<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdfbe1btt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdfbe1btt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-fast-outline" /></template>
