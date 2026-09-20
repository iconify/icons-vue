<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwpg2abjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwpg2abjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ancient-pavilion-fill" /></template>
