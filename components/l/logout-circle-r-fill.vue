<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsv_9ebej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsv_9ebej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:logout-circle-r-fill" /></template>
