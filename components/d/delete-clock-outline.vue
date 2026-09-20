<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmkw2to-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmkw2to-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:delete-clock-outline" /></template>
