<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptbs4actm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptbs4actm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:helm" /></template>
