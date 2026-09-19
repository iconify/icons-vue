<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki1_cbb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ki1_cbb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:gooey-daemon" /></template>
