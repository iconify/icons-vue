<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8iorx6kd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c8iorx6kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:level-end-flag" /></template>
