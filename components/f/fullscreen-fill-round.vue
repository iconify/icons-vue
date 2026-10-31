<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0r1fobsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0r1fobsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fullscreen-fill-round" /></template>
