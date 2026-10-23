<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrvsvkmmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrvsvkmmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:cloudy" /></template>
