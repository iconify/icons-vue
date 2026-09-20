<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjbznwmxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjbznwmxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:camera-lens-fill" /></template>
