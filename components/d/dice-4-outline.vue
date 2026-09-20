<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd0csib2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd0csib2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dice-4-outline" /></template>
