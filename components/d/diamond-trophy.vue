<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk59f9vxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jk59f9vxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:diamond-trophy" /></template>
