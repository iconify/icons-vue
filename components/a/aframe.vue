<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mueq0oblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="mueq0oblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:aframe" /></template>
