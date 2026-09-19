<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5y942p5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5y942p5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:bounce-right" /></template>
