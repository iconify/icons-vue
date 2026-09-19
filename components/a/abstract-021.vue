<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3yxocp3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x3yxocp3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-021" /></template>
