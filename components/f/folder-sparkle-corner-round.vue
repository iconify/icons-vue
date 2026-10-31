<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg0qxwbdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg0qxwbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-sparkle-corner-round" /></template>
