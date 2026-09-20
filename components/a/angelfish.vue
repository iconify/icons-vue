<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jligmhj-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jligmhj-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:angelfish" /></template>
