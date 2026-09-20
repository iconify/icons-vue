<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fikz1-bul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fikz1-bul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dice" /></template>
