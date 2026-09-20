<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-g_mmeuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-g_mmeuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-multiple-outline" /></template>
