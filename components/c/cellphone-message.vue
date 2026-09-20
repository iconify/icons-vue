<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9q2_w4fy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9q2_w4fy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cellphone-message" /></template>
