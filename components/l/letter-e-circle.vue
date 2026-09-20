<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inglbibcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inglbibcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:letter-e-circle" /></template>
