<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky8-f3bot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ky8-f3bot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:boxes-search" /></template>
