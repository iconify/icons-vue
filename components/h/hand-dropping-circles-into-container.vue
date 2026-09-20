<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb8bgqbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lb8bgqbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:hand-dropping-circles-into-container" /></template>
