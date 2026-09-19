<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzkzsgj6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kzkzsgj6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crystal-growth" /></template>
