<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st6p60b2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="st6p60b2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cactus-2-fill" /></template>
