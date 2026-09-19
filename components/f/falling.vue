<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/joamw7nrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="joamw7nrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:falling" /></template>
