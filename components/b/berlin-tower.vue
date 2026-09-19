<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxlx8t3pw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxlx8t3pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:berlin-tower" /></template>
