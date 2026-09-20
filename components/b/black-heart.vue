<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc39e3tng.css';
import '../../css/f/fq4_qkb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="mc39e3tng"/><path class="fq4_qkb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:black-heart" /></template>
