<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etkz65bcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etkz65bcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:box-location-outline" /></template>
