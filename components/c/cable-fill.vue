<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo1tmdbjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eo1tmdbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cable-fill" /></template>
