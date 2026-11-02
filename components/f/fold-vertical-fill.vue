<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdhb_e1dj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdhb_e1dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fold-vertical-fill" /></template>
