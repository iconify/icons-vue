<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aea8_4biy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aea8_4biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:face-surprised-round" /></template>
