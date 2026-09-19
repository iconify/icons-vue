<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3vw9pxmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n3vw9pxmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bo" /></template>
