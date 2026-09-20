<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l46mue4pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l46mue4pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:heart-2-fill" /></template>
