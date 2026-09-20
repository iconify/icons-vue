<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6uk6ybbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6uk6ybbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:gas-station-line" /></template>
