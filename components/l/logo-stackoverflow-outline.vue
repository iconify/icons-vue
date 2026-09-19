<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpbhyqbff.css';
import '../../css/j/jl37fgbdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cpbhyqbff"/><path class="jl37fgbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-stackoverflow-outline" /></template>
