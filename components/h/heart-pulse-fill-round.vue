<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpr5abczk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpr5abczk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heart-pulse-fill-round" /></template>
