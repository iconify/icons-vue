<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gk_dwhbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gk_dwhbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-love" /></template>
