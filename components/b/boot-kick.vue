<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccaxjcfjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ccaxjcfjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:boot-kick" /></template>
