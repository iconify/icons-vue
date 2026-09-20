<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h16ti1b7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h16ti1b7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:entertainment-events-hobbies-chess-pawn" /></template>
