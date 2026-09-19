<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka0h_3b8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ka0h_3b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:falling-leaf" /></template>
