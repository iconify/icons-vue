<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzze5jbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rzze5jbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:chili-pepper" /></template>
