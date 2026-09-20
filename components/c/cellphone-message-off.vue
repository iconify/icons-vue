<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwa1_bb1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwa1_bb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cellphone-message-off" /></template>
