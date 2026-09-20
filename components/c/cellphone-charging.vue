<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0ukv68fm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0ukv68fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cellphone-charging" /></template>
