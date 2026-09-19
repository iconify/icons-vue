<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azqwpqbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="azqwpqbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:bluetooth" /></template>
