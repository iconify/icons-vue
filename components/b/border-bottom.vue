<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw1a0h_9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="vw1a0h_9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:border-bottom" /></template>
