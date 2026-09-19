<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjlhq0b_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vjlhq0b_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bloody-sword" /></template>
