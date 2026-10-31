<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksutv4lbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksutv4lbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-turn-left-up-duotone-round" /></template>
