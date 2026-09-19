<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbkl6_-bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mbkl6_-bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-king-diamonds" /></template>
