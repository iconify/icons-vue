<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9wkehbwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q9wkehbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:brain-stem" /></template>
