<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp0fyhbud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cp0fyhbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cellphone-screenshot" /></template>
