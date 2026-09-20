<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0w57-1ir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0w57-1ir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clock-time-eleven-outline" /></template>
