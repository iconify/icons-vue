<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x93dmqdrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x93dmqdrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:board-writing-3" /></template>
