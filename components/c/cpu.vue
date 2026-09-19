<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1n_oqbpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s1n_oqbpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cpu" /></template>
