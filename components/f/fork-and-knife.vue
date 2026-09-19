<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pugxtmbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pugxtmbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:fork-and-knife" /></template>
