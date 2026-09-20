<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fou3p8ybm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fou3p8ybm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:inbox-favorite-remix" /></template>
