<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbweqf9zu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pbweqf9zu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hatchets" /></template>
