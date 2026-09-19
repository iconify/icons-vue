<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehgrw2b_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ehgrw2b_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:frog-mouth-helm" /></template>
