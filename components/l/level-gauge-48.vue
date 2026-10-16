<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl870bc1m.css';
import '../../css/t/te3lkr3kc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jl870bc1m"/><path class="te3lkr3kc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:level-gauge-48" /></template>
