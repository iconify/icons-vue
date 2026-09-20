<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqms5zblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqms5zblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:debug-step-into" /></template>
