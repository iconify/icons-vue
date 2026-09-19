<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgwihvb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jgwihvb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:froe-and-mallet" /></template>
