<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r71onbhuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r71onbhuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:classical-knowledge" /></template>
