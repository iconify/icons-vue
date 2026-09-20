<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mm4gcybwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mm4gcybwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bag-suitcase-1-remix" /></template>
