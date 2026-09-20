<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpi7ur37t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpi7ur37t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-start-horizontal" /></template>
