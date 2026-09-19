<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri5yisb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":24};
const content = `<path class="ri5yisb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:dinners-club" /></template>
