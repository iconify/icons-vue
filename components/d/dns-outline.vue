<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iiaha8smm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iiaha8smm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dns-outline" /></template>
