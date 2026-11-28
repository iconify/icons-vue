<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmbgeltxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmbgeltxp primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:fit-height-duotone" /></template>
