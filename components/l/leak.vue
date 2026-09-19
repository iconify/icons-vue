<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt-0_eb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jt-0_eb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:leak" /></template>
