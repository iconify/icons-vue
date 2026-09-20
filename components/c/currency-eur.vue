<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu24srbui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tu24srbui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:currency-eur" /></template>
