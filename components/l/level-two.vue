<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7vlnacju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a7vlnacju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:level-two" /></template>
