<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jncd0gk1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jncd0gk1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:daggers" /></template>
