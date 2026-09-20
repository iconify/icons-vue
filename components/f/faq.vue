<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmesgm11x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmesgm11x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:faq" /></template>
