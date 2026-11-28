<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tweod6bqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tweod6bqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:heart-pulse-solid" /></template>
