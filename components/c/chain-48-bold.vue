<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcazebc-h.css';
import '../../css/r/r09w33bfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fcazebc-h"/><path class="r09w33bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chain-48-bold" /></template>
