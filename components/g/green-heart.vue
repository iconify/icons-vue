<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp5t1es6g.css';
import '../../css/f/fq4_qkb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="cp5t1es6g"/><path class="fq4_qkb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:green-heart" /></template>
