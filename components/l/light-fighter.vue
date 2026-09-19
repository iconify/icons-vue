<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3h_-gbgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l3h_-gbgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:light-fighter" /></template>
