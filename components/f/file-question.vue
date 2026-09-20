<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnty1nisa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnty1nisa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-question" /></template>
