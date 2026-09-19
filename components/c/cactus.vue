<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in1naxb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="in1naxb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cactus" /></template>
