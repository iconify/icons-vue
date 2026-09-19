<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2zt6obtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u2zt6obtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:eagle-emblem" /></template>
