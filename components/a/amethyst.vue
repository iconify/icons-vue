<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doftgs7xm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="doftgs7xm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:amethyst" /></template>
