<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmmr71bba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmmr71bba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:event-week-outline" /></template>
