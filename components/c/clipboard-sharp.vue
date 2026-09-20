<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_c9h_pwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_c9h_pwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:clipboard-sharp" /></template>
