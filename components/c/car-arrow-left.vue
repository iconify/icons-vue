<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hijaslbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hijaslbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-arrow-left" /></template>
