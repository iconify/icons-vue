<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhb2hvx3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhb2hvx3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-dollar-line" /></template>
