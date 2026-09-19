<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl14hb56d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jl14hb56d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hammer-drop" /></template>
