<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcypmmoky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcypmmoky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:food-steak-off" /></template>
