<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm2clvi6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1920,"height":1280};
const content = `<path class="cm2clvi6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:keyboard-o" /></template>
