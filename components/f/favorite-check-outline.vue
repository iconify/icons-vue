<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os2ovpicr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="os2ovpicr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:favorite-check-outline" /></template>
