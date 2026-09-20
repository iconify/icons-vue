<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r60m7nbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r60m7nbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-line-up" /></template>
