<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv9wz8bnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kv9wz8bnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:door-handle" /></template>
