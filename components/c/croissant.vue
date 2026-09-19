<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pskodmbms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pskodmbms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:croissant" /></template>
