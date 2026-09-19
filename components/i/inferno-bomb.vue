<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua8thwjmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ua8thwjmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:inferno-bomb" /></template>
