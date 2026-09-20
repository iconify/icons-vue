<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9o76f74w.css';
import '../../css/f/fq4_qkb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="q9o76f74w"/><path class="fq4_qkb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:blue-heart" /></template>
