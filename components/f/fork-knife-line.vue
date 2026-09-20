<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvgm96bxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvgm96bxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fork-knife-line" /></template>
