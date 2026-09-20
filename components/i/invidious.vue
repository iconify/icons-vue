<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k65o28biy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k65o28biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:invidious" /></template>
