<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tejl1ydti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tejl1ydti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bridge" /></template>
