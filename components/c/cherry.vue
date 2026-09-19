<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udo-y3bir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="udo-y3bir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cherry" /></template>
