<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh47_j5vu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uh47_j5vu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fire-iris" /></template>
