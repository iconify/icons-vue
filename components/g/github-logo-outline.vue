<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6o5rl8bt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="github-logo-outline"><path class="(Stroke) Vector c6o5rl8bt" clip-rule="evenodd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:github-logo-outline" /></template>
