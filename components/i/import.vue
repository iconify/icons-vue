<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo55s0bnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jo55s0bnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:import" /></template>
