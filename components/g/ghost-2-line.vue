<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryd3g7nyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryd3g7nyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ghost-2-line" /></template>
