<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba82wobrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba82wobrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-text-multiple-outline" /></template>
