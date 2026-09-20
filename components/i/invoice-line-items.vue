<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw7aaducw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rw7aaducw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-line-items" /></template>
