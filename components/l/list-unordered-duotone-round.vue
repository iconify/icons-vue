<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfdd8xbro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfdd8xbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-unordered-duotone-round" /></template>
