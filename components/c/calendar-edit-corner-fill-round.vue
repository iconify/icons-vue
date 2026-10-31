<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpeglj27v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpeglj27v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-edit-corner-fill-round" /></template>
