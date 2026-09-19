<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne25vkbnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ne25vkbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:jellyfish" /></template>
