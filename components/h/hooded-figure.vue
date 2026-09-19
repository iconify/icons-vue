<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt1tedbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tt1tedbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hooded-figure" /></template>
