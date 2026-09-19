<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtexm5bmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rtexm5bmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-067" /></template>
