<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz3vbkbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iz3vbkbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lamprey-mouth" /></template>
