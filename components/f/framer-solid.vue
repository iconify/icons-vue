<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr7z-mv3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dr7z-mv3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:framer-solid" /></template>
