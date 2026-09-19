<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imlplj1lz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imlplj1lz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:camera-movie" /></template>
