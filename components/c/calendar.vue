<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwa_0acop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwa_0acop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:calendar" /></template>
