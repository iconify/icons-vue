<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/biwqd-khk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="biwqd-khk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:infinity-glyph" /></template>
