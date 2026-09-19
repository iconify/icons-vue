<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llwij-lic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="llwij-lic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:energy-sword" /></template>
