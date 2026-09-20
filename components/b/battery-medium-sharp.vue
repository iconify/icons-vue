<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mljm37bxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mljm37bxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:battery-medium-sharp" /></template>
