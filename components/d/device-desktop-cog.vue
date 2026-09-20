<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck5ihzb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck5ihzb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-desktop-cog" /></template>
