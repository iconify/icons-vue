<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru0y2vl2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru0y2vl2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:application-brackets-outline" /></template>
