<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqw4w29bz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqw4w29bz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:commodore" /></template>
