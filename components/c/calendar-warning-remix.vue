<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih_w5bcgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ih_w5bcgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:calendar-warning-remix" /></template>
