<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efrk3ebbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efrk3ebbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:football" /></template>
