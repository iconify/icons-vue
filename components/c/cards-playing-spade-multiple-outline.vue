<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oni-ybbts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oni-ybbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cards-playing-spade-multiple-outline" /></template>
