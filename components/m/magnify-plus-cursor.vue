<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hinf7eusg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hinf7eusg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:magnify-plus-cursor" /></template>
