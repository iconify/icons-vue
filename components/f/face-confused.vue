<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anh6pktus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anh6pktus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:face-confused" /></template>
