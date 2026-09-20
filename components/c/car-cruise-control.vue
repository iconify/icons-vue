<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_jgs3bwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_jgs3bwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-cruise-control" /></template>
