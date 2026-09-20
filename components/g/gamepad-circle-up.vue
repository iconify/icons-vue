<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp6inmbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dp6inmbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gamepad-circle-up" /></template>
