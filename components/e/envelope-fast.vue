<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbo5by-jd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbo5by-jd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:envelope-fast" /></template>
