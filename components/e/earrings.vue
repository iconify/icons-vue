<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9s6c3bix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n9s6c3bix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:earrings" /></template>
