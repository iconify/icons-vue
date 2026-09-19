<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1w6rmbcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1w6rmbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:full-screen" /></template>
