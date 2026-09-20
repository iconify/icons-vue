<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h54sdng5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h54sdng5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:block-bell-notification-remix" /></template>
