<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_uzs2cum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_uzs2cum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:cell-2x2" /></template>
