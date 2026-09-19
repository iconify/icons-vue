<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im916tbmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="im916tbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bowl-spiral" /></template>
