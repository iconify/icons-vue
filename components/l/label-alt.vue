<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aega1vbyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aega1vbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:label-alt" /></template>
