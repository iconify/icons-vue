<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd21t8b0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fd21t8b0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-game-controller-a" /></template>
