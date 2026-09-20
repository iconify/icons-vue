<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xksjs3hev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xksjs3hev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:greeting-card-open" /></template>
