<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnckoc04l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnckoc04l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-electric" /></template>
