<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8xay6bvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g8xay6bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:claymore-explosive" /></template>
