<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq1ifdc2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq1ifdc2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:badge-5k" /></template>
