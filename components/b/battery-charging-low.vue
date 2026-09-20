<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk3_t9boi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fk3_t9boi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-charging-low" /></template>
