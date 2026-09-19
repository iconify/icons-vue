<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9iptvk5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g9iptvk5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-4-diamonds" /></template>
