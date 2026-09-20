<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gptt6rb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gptt6rb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:keyboard-erase" /></template>
