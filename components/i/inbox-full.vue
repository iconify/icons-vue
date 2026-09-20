<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqhoic-6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqhoic-6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:inbox-full" /></template>
