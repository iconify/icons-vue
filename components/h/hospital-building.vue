<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8izv0bqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8izv0bqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hospital-building" /></template>
