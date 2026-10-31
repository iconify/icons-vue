<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knu0x1b-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knu0x1b-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-big-right-round" /></template>
