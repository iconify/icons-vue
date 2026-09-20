<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyooy8g6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyooy8g6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoji-neutral" /></template>
