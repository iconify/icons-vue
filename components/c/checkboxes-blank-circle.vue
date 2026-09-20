<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8bzg1bfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8bzg1bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:checkboxes-blank-circle" /></template>
