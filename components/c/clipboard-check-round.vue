<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks0phgbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ks0phgbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-check-round" /></template>
