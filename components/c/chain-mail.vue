<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4q5tli9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z4q5tli9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:chain-mail" /></template>
