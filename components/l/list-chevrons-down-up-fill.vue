<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhz_pd5hu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhz_pd5hu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-chevrons-down-up-fill" /></template>
