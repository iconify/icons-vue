<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvjyayb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvjyayb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:heart-pulse-solid" /></template>
