<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj1uhs6yz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kj1uhs6yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:barracks" /></template>
