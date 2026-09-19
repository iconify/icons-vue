<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0q3tqbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y0q3tqbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:expand-down" /></template>
