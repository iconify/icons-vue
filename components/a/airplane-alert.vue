<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icm1kqhqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icm1kqhqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:airplane-alert" /></template>
