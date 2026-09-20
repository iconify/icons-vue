<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnykq_boq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnykq_boq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bug-pause-outline" /></template>
