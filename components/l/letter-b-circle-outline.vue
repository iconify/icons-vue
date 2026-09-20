<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbkxeac3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbkxeac3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:letter-b-circle-outline" /></template>
