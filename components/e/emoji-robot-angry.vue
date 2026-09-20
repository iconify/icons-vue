<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk9z7dtrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tk9z7dtrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoji-robot-angry" /></template>
