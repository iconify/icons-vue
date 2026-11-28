<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv03ee_gy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hv03ee_gy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:gamepad-check" /></template>
