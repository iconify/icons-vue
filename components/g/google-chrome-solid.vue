<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g34ucr9rq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g34ucr9rq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:google-chrome-solid" /></template>
