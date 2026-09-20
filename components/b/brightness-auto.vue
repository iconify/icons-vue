<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygi1bib1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygi1bib1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:brightness-auto" /></template>
