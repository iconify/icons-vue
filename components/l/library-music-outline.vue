<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iduxaeb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iduxaeb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:library-music-outline" /></template>
