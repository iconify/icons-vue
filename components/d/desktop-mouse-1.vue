<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os1b52jwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="os1b52jwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:desktop-mouse-1" /></template>
