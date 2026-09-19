<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfmm-1b7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kfmm-1b7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:chips-bag" /></template>
