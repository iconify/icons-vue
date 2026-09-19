<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9vtyyb-e.css';
import '../../css/c/ca5ecz53l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u9vtyyb-e"/><path class="ca5ecz53l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-format" /></template>
