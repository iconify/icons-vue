<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5ig3rb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5ig3rb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:add-circle" /></template>
