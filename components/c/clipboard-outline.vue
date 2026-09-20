<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt6g47bfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt6g47bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-outline" /></template>
