<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc2jgs14m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hc2jgs14m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:diamond-ring-fill" /></template>
