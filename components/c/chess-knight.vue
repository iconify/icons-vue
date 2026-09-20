<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hipazkb2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hipazkb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chess-knight" /></template>
