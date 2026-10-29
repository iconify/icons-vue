<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i80tytbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i80tytbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bot-message-square-solid" /></template>
