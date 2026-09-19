<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml7-_x_yg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml7-_x_yg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:luggage-check-in" /></template>
