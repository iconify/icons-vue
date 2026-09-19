<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csh7irwwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="csh7irwwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:flamethrower" /></template>
