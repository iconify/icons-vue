<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmg3tgb0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmg3tgb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:crop" /></template>
