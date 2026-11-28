<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/codh4ybyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="codh4ybyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:heart-pulse-check" /></template>
