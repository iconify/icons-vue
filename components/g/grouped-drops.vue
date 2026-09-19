<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax8xvyb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ax8xvyb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:grouped-drops" /></template>
