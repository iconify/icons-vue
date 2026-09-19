<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brsyw1b9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="brsyw1b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:box-trap" /></template>
