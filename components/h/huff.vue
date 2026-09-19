<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdggcu0gw.css';
import '../../css/s/sljodwyif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rdggcu0gw"/><path class="sljodwyif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:huff" /></template>
