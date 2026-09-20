<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t82-41b5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t82-41b5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gate-buffer" /></template>
