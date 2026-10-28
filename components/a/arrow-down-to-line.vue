<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ga0_vkbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ga0_vkbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-down-to-line" /></template>
