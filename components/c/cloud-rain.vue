<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfxxddc6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mfxxddc6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:cloud-rain" /></template>
