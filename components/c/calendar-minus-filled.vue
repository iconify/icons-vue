<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em-bjibae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="em-bjibae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:calendar-minus-filled" /></template>
