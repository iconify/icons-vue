<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mabm5lwov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mabm5lwov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:camera-plus-outline" /></template>
