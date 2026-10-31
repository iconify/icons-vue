<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co2rlf7fm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="co2rlf7fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bold-round" /></template>
