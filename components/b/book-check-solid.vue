<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x88vwgbmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x88vwgbmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:book-check-solid" /></template>
