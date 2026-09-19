<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/touuu46vk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="touuu46vk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:frame" /></template>
