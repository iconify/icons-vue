<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0e4x_mua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f0e4x_mua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:building-bolt-door" /></template>
