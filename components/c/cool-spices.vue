<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzhbwo53x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lzhbwo53x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cool-spices" /></template>
