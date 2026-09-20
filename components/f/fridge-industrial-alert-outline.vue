<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivv9obcxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivv9obcxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fridge-industrial-alert-outline" /></template>
