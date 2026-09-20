<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcnkvbbth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcnkvbbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:induction" /></template>
