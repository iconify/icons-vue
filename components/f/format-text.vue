<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcie1_bky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="hcie1_bky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:format-text" /></template>
