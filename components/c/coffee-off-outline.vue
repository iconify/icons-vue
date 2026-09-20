<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orpklqf2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orpklqf2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:coffee-off-outline" /></template>
