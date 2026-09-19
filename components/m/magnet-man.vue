<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js-wdwglr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="js-wdwglr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:magnet-man" /></template>
