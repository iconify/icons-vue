<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prx_0ebow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="prx_0ebow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bouncing-spring" /></template>
