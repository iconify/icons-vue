<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2f1anxyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2f1anxyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:copy-x" /></template>
