<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtmoj1brt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtmoj1brt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:heat-wave" /></template>
