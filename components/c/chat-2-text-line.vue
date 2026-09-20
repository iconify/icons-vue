<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jecgmcqwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jecgmcqwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:chat-2-text-line" /></template>
