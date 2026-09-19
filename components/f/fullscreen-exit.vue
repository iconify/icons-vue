<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjfyme04j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjfyme04j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:fullscreen-exit" /></template>
