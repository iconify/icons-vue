<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv22vxlfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cv22vxlfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cog-refresh" /></template>
