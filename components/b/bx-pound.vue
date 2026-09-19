<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnnwubjuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnnwubjuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-pound" /></template>
