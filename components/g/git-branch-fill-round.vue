<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_weskb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_weskb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-branch-fill-round" /></template>
