<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4yvs6fct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4yvs6fct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:face-sick-outline" /></template>
