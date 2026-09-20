<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzkd7_b7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzkd7_b7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-add" /></template>
