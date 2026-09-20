<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdg6ipbwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdg6ipbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fanfou" /></template>
