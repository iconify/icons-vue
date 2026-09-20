<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce6ad26an.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ce6ad26an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ink-minus" /></template>
