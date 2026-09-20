<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad63tmb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ad63tmb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-left-drop-circle" /></template>
