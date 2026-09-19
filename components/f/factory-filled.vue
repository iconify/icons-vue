<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i50hvfb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i50hvfb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:factory-filled" /></template>
