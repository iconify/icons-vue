<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unu9fbpdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gitlab-logo-outline"><path class="(Stroke) Vector unu9fbpdc" clip-rule="evenodd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:gitlab-logo-outline" /></template>
