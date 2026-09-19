<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b799n1bqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b799n1bqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fox" /></template>
