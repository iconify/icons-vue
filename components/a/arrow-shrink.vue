<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijw27cjpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ijw27cjpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:arrow-shrink" /></template>
