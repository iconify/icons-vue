<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmlna1m4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmlna1m4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-sync" /></template>
