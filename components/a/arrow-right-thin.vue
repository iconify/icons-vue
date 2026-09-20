<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcu9tlrct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcu9tlrct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-right-thin" /></template>
