<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3j8hc2km.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z3j8hc2km"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:elderberry" /></template>
