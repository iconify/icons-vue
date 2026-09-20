<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_x7_ybez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_x7_ybez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:discord-line" /></template>
