<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjgx2qbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjgx2qbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:laptop-fill-round" /></template>
