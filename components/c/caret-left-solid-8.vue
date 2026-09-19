<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5nbq8jeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="x5nbq8jeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:caret-left-solid-8" /></template>
