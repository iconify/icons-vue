<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b47e4sbey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b47e4sbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:ice-cream-bowl" /></template>
