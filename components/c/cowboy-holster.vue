<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7jdv5g2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h7jdv5g2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cowboy-holster" /></template>
