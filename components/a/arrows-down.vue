<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbn6__bej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbn6__bej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrows-down" /></template>
