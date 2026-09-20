<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1r_d5pul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1r_d5pul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:camera-switch-fill" /></template>
