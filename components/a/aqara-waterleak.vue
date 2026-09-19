<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2tv6bbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2tv6bbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-waterleak" /></template>
