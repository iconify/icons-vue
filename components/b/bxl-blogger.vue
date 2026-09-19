<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhk70wg4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhk70wg4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-blogger" /></template>
