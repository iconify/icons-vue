<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt86abese.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bt86abese"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:handled-teacup-and-saucer-and-wifi" /></template>
