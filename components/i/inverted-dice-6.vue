<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en51l1bxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="en51l1bxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:inverted-dice-6" /></template>
