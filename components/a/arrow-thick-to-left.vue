<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1yv9abga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j1yv9abga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:arrow-thick-to-left" /></template>
