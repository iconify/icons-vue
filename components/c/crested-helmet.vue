<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn-w70mvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zn-w70mvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crested-helmet" /></template>
