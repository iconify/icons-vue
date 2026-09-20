<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvbsqfmzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvbsqfmzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:cactus-line" /></template>
