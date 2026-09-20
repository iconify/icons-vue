<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw1d0pbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mw1d0pbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:chess-knight" /></template>
