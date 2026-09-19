<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6k88_b8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w6k88_b8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:knife-fork" /></template>
