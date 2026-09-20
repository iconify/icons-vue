<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzghf5blm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzghf5blm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-powerpoint-box-outline" /></template>
