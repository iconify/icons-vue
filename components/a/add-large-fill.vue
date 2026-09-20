<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eca3_qbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eca3_qbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:add-large-fill" /></template>
