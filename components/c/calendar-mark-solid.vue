<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouox2hb3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ouox2hb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:calendar-mark-solid" /></template>
