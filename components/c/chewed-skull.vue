<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j37pk-bgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j37pk-bgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:chewed-skull" /></template>
