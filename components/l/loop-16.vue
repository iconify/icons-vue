<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iosgfqbhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iosgfqbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:loop-16" /></template>
