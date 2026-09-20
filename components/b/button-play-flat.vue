<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-izh3bji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q-izh3bji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:button-play-flat" /></template>
