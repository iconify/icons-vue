<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc8e2ob0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gc8e2ob0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:goose" /></template>
