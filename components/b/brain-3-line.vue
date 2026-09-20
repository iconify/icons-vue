<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsqdo2byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsqdo2byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:brain-3-line" /></template>
