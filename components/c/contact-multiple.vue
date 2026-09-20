<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh2n31bax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wh2n31bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:contact-multiple" /></template>
