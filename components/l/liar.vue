<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q53r2u7fs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q53r2u7fs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:liar" /></template>
