<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mak933byo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mak933byo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bus-location" /></template>
