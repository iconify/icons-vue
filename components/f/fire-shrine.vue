<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3n1nwowy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p3n1nwowy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fire-shrine" /></template>
