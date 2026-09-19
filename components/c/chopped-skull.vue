<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-5-ogo-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s-5-ogo-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:chopped-skull" /></template>
