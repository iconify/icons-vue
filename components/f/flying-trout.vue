<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp37l5bbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yp37l5bbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:flying-trout" /></template>
