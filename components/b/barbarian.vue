<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4z1edbsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v4z1edbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:barbarian" /></template>
